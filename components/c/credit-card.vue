<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vweeopo2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vweeopo2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:credit-card" /></template>
