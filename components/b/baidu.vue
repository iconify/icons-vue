<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-st_b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="jr-st_b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:baidu" /></template>
