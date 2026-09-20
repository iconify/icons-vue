<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er63n8b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er63n8b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-minus-outline" /></template>
