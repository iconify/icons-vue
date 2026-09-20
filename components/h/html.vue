<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yx251zbnn.css';
import '../../css/p/pr1ptmzlj.css';
import '../../css/k/ks9331tco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="yx251zbnn"/><path class="pr1ptmzlj"/><path class="ks9331tco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="skill-icons:html" /></template>
