<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd93nu3lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wd93nu3lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:help-outlined" /></template>
