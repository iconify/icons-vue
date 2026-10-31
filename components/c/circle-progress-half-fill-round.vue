<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojcapjb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojcapjb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-progress-half-fill-round" /></template>
