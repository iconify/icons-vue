<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slw0lyzha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slw0lyzha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:filter-fill" /></template>
