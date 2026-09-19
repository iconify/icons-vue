<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6rk1e3su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6rk1e3su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:inbox-arrow-down" /></template>
