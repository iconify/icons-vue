<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sef8m5cia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sef8m5cia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-lock" /></template>
