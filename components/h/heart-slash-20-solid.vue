<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8kch-une.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x8kch-une"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heart-slash-20-solid" /></template>
