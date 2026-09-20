<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au5lyab1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au5lyab1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-bottom-right" /></template>
