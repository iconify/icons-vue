<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjt7edbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjt7edbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-search-outline" /></template>
