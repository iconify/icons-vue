<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdvk-d6wd.css';
import '../../css/a/a6npavb3q.css';
import '../../css/h/hp-glnvum.css';
import '../../css/l/l-cgyhben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="gdvk-d6wd"><circle class="a6npavb3q"/><circle class="hp-glnvum"/><path class="l-cgyhben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:binoculars-outline" /></template>
