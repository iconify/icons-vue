<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_byl6bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_byl6bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots" /></template>
