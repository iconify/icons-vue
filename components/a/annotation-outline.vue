<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjocmgb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjocmgb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:annotation-outline" /></template>
