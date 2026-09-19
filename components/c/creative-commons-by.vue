<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg7x33b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cg7x33b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons-by" /></template>
