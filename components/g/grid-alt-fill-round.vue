<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj14bacvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj14bacvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:grid-alt-fill-round" /></template>
