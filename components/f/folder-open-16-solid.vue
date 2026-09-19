<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6vko2bzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w6vko2bzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-open-16-solid" /></template>
