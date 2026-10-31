<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j9-zgabka.css';
import '../../css/m/m8oyeebcd.css';
import '../../css/x/xtu-11phh.css';
import '../../css/y/y35zxvrfv.css';
import '../../css/z/z-u4nnbit.css';
import '../../css/i/i3dzmtb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j9-zgabka wm-k"/><path class="m8oyeebcd wm-k"/><path class="wm-k xtu-11phh"/><path class="wm-shadow y35zxvrfv"/><path class="wm-shine z-u4nnbit"/><path class="i3dzmtb9d wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:calculator" /></template>
