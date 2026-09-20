<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khd9gq-js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="khd9gq-js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-earpod-sound" /></template>
