<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/s_odbi9ry.css';
import '../../css/k/koi_40_qj.css';
import '../../css/t/t7mwtvffu.css';
import '../../css/b/b99_c-p4h.css';
import '../../css/m/mk0jyeo_d.css';
import '../../css/c/comv-1dst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="s_odbi9ry wm-deco"/><path class="koi_40_qj wm-deco"/><path class="t7mwtvffu wm-k"/><path class="b99_c-p4h wm-a"/><path class="mk0jyeo_d wm-k"/><path class="comv-1dst wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-tree-blueprint" /></template>
