<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8_9rfgus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8_9rfgus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3" /></template>
