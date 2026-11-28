<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpf0_218d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lpf0_218d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-warning-fill" /></template>
