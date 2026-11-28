<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga3xw3bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga3xw3bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hanger" /></template>
