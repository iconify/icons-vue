<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in40wib8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="in40wib8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gmail-cleaner-dark" /></template>
