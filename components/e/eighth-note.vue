<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/ajlzracvz.css';
import '../../css/c/c55ag9btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ajlzracvz"/><circle class="c55ag9btm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:eighth-note" /></template>
