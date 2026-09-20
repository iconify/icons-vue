<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccdje9g3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccdje9g3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-battery-outline" /></template>
