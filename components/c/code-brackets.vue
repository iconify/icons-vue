<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx946we4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx946we4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-brackets" /></template>
