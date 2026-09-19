<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgoy5g6-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cgoy5g6-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:camera-reverse" /></template>
