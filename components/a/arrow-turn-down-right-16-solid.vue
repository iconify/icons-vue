<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wty1f8g4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wty1f8g4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-down-right-16-solid" /></template>
