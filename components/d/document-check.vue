<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x12oh9b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x12oh9b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:document-check" /></template>
