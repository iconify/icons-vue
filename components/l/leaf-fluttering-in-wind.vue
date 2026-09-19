<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cbt3z_bte.css';
import '../../css/p/p--54x55y.css';
import '../../css/s/sl4-7z0-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="cbt3z_bte"/><path class="p--54x55y"/><path class="sl4-7z0-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:leaf-fluttering-in-wind" /></template>
