<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au9uxsvgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au9uxsvgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:atom-2-filled" /></template>
