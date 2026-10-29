<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/c/cgssfdcel.css';
import '../../css/d/dlb4_kl3b.css';
import '../../css/x/xj9-8y3fv.css';
import '../../css/p/phmwp8b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="cgssfdcel wm-deco"/><path class="dlb4_kl3b wm-deco"/><path class="xj9-8y3fv"/><path class="phmwp8b9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-up-down-blueprint" /></template>
