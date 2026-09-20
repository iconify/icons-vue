<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek4thtbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek4thtbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:globe" /></template>
