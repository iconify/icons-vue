<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4d9uq82f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y4d9uq82f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:crosshairs-solid" /></template>
