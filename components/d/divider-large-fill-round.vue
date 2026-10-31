<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oay8kys0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oay8kys0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divider-large-fill-round" /></template>
