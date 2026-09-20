<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyd6nsb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyd6nsb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:accessibility-solid" /></template>
