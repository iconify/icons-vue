<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og44e43fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og44e43fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cart-x-solid" /></template>
