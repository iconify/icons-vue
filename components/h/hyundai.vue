<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv4vqusdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv4vqusdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hyundai" /></template>
