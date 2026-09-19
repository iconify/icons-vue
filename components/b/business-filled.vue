<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxz9krbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxz9krbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:business-filled" /></template>
