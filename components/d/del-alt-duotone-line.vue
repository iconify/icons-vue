<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tv5tdk3ma.css';
import '../../css/n/nlcw3p9xy.css';
import '../../css/g/ghtk6ab_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tv5tdk3ma"/><ellipse class="nlcw3p9xy"/><path class="ghtk6ab_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:del-alt-duotone-line" /></template>
