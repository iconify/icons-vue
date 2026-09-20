<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my14qkbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my14qkbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter3" /></template>
