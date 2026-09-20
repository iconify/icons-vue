<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb8yqhies.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wb8yqhies"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:funnel-dollar-solid" /></template>
