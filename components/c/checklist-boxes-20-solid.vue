<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xvbwbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w4xvbwbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist-boxes-20-solid" /></template>
