<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9cb03m5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9cb03m5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cloud-cog-fill" /></template>
