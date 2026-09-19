<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg6nrp1ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":608,"height":1280};
const content = `<g transform="translate(608 0) scale(-1 1)"><path class="rg6nrp1ic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:angle-right" /></template>
