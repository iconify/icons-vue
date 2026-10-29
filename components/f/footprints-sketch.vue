<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e3728q2fv.css';
import '../../css/j/j1tznqzdp.css';
import '../../css/y/ykgkceq4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e3728q2fv"/><path class="j1tznqzdp wm-k"/><path class="wm-a ykgkceq4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:footprints-sketch" /></template>
