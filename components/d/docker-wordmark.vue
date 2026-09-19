<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmts22b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wmts22b7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:docker-wordmark" /></template>
