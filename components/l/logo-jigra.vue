<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikyvzsb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikyvzsb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-jigra" /></template>
