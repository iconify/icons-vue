<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avwo5dbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avwo5dbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:filter-line" /></template>
