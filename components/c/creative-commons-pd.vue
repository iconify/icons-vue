<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7eeem2yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r7eeem2yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons-pd" /></template>
