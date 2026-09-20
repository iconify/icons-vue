<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azqc4mbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azqc4mbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-hexagon-filled" /></template>
