<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb5bfclwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb5bfclwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-up-left-solid" /></template>
