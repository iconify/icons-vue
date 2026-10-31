<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw1cj3bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw1cj3bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-minus-round" /></template>
