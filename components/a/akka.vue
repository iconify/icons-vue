<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf8n3pwcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yf8n3pwcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:akka" /></template>
