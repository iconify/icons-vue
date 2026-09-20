<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cazappszh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cazappszh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bank-card-2-line" /></template>
