<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_74gcnmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_74gcnmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-w-circle" /></template>
