<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9tzgwbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9tzgwbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-alt-x" /></template>
