<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw972ynsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fw972ynsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-down-solid" /></template>
