<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9rxa3bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9rxa3bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:auto-stories" /></template>
