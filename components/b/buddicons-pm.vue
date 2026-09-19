<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttu2v-2ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ttu2v-2ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:buddicons-pm" /></template>
