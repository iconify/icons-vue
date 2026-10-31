<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d60tyn8oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d60tyn8oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coolicons-round" /></template>
