<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkmq8ioen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkmq8ioen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:aperture-sharp" /></template>
