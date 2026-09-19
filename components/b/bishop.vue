<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki65vkfie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki65vkfie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:bishop" /></template>
