<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk_as72bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nk_as72bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cloud-sun-rain-solid" /></template>
