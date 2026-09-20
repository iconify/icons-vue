<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttdwwrvcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttdwwrvcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-arrow-up-down-outline" /></template>
