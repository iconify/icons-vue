<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byuv76u1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="byuv76u1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-office-2-20-solid" /></template>
