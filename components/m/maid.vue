<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/smv78gb2a.css';
import '../../css/g/gdr6p71vl.css';
import '../../css/a/a5n3-3bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="smv78gb2a"/><path class="gdr6p71vl"/><path class="a5n3-3bfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:maid" /></template>
