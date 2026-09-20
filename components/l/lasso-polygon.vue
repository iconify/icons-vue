<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tu5q5obme.css';
import '../../css/f/f2ny9eb9g.css';
import '../../css/c/c00zy4e0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tu5q5obme"/><path class="f2ny9eb9g"/><path class="c00zy4e0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lasso-polygon" /></template>
