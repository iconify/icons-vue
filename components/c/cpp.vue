<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dwpiq9ban.css';
import '../../css/a/a139p7rye.css';
import '../../css/n/nz0lp3ozz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="dwpiq9ban"/><path class="a139p7rye"/><path class="nz0lp3ozz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:cpp" /></template>
