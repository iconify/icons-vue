<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omgkdvbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1408};
const content = `<path class="omgkdvbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:jsfiddle" /></template>
