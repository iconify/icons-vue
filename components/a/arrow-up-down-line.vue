<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdw75iamg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdw75iamg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-down-line" /></template>
