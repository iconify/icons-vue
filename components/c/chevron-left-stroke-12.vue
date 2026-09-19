<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5xoo-b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h5xoo-b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-left-stroke-12" /></template>
