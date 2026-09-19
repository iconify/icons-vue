<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us8wt9b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="us8wt9b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:aspect-ratio-alt" /></template>
