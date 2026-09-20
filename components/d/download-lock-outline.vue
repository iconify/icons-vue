<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwicvjowe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwicvjowe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-lock-outline" /></template>
