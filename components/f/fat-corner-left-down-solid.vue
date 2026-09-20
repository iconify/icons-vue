<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke7b5obcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke7b5obcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-left-down-solid" /></template>
