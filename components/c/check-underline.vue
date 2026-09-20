<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6kth5bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6kth5bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:check-underline" /></template>
