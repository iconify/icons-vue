<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l40jc9brz.css';
import '../../css/k/knv_kx8ky.css';
import '../../css/b/bek5jfb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l40jc9brz"/><path class="knv_kx8ky"/><path class="bek5jfb-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:golang" /></template>
