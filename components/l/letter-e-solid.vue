<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysdxcb4af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysdxcb4af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-e-solid" /></template>
