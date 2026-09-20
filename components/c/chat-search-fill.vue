<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmpu4c7qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmpu4c7qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-search-fill" /></template>
