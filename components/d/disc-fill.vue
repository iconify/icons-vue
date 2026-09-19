<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj-rdfpgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qj-rdfpgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:disc-fill" /></template>
