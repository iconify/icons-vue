<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njyy8qbmd.css';
import '../../css/f/f-ksdqydc.css';
import '../../css/k/k6t4853ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="njyy8qbmd"/><circle class="f-ksdqydc"/><path class="k6t4853ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-person-filled" /></template>
