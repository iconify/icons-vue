<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dah875bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dah875bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-exclamation" /></template>
