<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f53u21b8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="f53u21b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:arrow-missed" /></template>
