<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-di8ibbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-di8ibbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:home-smile-solid" /></template>
