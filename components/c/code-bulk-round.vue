<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7du0phez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7du0phez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:code-bulk-round" /></template>
