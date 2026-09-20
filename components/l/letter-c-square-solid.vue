<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypxxisb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypxxisb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-c-square-solid" /></template>
