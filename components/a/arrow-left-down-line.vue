<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fadjvvb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fadjvvb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-down-line" /></template>
