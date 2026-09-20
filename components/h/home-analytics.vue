<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s69kkir1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s69kkir1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:home-analytics" /></template>
