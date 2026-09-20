<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shqsojekt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shqsojekt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-circle" /></template>
