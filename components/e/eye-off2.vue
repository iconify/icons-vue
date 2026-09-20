<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r8zd38n0h.css';
import '../../css/g/gl1daib4n.css';
import '../../css/z/zw1qlkb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r8zd38n0h"/><path class="gl1daib4n"/><path class="zw1qlkb7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:eye-off2" /></template>
