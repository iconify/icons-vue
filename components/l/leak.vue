<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0prhdc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="j0prhdc4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:leak" /></template>
