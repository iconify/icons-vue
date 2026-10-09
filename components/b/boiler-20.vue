<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnezarb7y.css';
import '../../css/u/u-fc2jiif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nnezarb7y"/><path class="u-fc2jiif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:boiler-20" /></template>
