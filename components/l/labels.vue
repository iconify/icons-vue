<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsy3h9rol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":408};
const content = `<path class="rsy3h9rol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:labels" /></template>
