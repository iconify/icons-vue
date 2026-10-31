<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/che1q43ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="che1q43ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-big-up-fill-round" /></template>
