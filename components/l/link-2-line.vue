<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2n8w6boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2n8w6boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:link-2-line" /></template>
