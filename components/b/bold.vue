<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq9przbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-8.5,"top":-7};
const content = `<path class="uq9przbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bold" /></template>
