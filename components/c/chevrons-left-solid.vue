<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb15imbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tb15imbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevrons-left-solid" /></template>
