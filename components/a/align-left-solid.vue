<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjpy3bcjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjpy3bcjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-left-solid" /></template>
