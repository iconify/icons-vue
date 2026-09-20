<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7axg7sef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7axg7sef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-save-alert-outline" /></template>
