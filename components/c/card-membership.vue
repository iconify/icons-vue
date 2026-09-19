<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4b9_fbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="k4b9_fbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:card-membership" /></template>
