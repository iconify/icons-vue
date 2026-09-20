<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo31okmzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo31okmzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-5-line" /></template>
