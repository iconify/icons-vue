<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rumqvjbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rumqvjbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:all-inclusive" /></template>
