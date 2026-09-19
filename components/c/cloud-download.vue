<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyyr9brib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyyr9brib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:cloud-download" /></template>
