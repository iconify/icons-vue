<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yazfd-bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yazfd-bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:adjustments-vertical" /></template>
