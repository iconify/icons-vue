<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d93dmed3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d93dmed3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-cursor-1-remix" /></template>
