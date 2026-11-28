<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vatnj1w-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vatnj1w-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-clock" /></template>
