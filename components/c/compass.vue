<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn3rdabgq.css';
import '../../css/f/fi_q30xur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="fn3rdabgq"/><path class="fi_q30xur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:compass" /></template>
