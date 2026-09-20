<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyaf8byaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyaf8byaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-transfer-outline" /></template>
