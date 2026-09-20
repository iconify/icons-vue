<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meuh_2vbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="meuh_2vbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-left" /></template>
