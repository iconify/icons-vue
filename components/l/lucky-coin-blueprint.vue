<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/su9dgwoey.css';
import '../../css/k/ku-38s29b.css';
import '../../css/z/zj798is8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="su9dgwoey wm-deco"/><path class="ku-38s29b wm-k"/><path class="wm-a zj798is8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lucky-coin-blueprint" /></template>
