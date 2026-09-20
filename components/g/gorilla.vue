<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw0i9f9gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0i9f9gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:gorilla" /></template>
