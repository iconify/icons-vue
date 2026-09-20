<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en0_7acrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en0_7acrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:docker" /></template>
