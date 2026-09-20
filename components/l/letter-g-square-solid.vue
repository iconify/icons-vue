<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsh1hrhbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsh1hrhbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-g-square-solid" /></template>
