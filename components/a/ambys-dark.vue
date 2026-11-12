<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y95_2sb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y95_2sb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ambys-dark" /></template>
