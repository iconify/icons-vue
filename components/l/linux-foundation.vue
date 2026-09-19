<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo8h1vk8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uo8h1vk8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:linux-foundation" /></template>
