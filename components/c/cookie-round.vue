<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h083lj9da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h083lj9da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cookie-round" /></template>
