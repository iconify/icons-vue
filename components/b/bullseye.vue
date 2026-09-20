<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umtc5tvss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umtc5tvss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bullseye" /></template>
