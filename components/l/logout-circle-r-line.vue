<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrhzn-qkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrhzn-qkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-circle-r-line" /></template>
