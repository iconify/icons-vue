<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnxj8rb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="jnxj8rb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:download" /></template>
