<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds5xzyo8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ds5xzyo8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gatsby-dark" /></template>
