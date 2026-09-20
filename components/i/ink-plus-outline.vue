<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omu4_-bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omu4_-bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ink-plus-outline" /></template>
