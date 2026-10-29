<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9-giub2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9-giub2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-dashed" /></template>
