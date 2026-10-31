<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6pxjjb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6pxjjb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-small-round" /></template>
