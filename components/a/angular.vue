<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjhvk6baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjhvk6baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:angular" /></template>
