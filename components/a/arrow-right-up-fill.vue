<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwv-rhboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwv-rhboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-up-fill" /></template>
