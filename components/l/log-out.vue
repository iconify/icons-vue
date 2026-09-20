<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxsb-j4xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="wxsb-j4xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:log-out" /></template>
