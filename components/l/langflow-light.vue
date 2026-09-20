<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7ee9ybej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7ee9ybej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:langflow-light" /></template>
