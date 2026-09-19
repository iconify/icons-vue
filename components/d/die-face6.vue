<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr2w7xw8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qr2w7xw8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face6" /></template>
