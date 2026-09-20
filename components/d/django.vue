<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z0vefwbox.css';
import '../../css/j/jm2s9ur2m.css';
import '../../css/b/bm30rmb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="z0vefwbox"/><path class="jm2s9ur2m"/><path class="bm30rmb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:django" /></template>
