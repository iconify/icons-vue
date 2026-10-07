<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgvtz8b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgvtz8b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lens-convex" /></template>
