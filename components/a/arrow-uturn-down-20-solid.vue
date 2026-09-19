<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khi1fr4mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="khi1fr4mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-down-20-solid" /></template>
