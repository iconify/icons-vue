<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whsca8c2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whsca8c2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-down-long-line" /></template>
