<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrjuz9bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrjuz9bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:heart-off" /></template>
