<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4q9k1w2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4q9k1w2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:docker" /></template>
