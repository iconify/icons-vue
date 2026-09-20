<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy8rzb4wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vy8rzb4wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bath-outline" /></template>
