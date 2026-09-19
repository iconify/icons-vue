<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9vk0igpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m9vk0igpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:burger" /></template>
