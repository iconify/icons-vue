<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i68-4kbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i68-4kbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:buy-me-a-coffee-dark" /></template>
