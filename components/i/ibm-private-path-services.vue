<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay4scmbps.css';
import '../../css/f/fave5fbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ay4scmbps"/><path class="fave5fbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-private-path-services" /></template>
