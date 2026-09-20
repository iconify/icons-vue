<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gow1o793z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gow1o793z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:baseball-diamond-outline" /></template>
