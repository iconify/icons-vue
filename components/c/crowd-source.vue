<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnqzk1bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnqzk1bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crowd-source" /></template>
