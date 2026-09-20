<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx-2lwb9f.css';
import '../../css/a/atjk8mbde.css';
import '../../css/a/a9o5t_b5e.css';
import '../../css/p/pnfsjvx9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="bx-2lwb9f"/><g class="atjk8mbde"><path class="a9o5t_b5e"/><path class="pnfsjvx9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:geogebra" /></template>
