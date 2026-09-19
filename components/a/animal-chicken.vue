<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxhtjnb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wxhtjnb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-chicken" /></template>
