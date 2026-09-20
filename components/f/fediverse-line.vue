<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccv0f09co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccv0f09co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fediverse-line" /></template>
