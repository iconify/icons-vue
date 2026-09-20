<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yovfahbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yovfahbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-plus-outline" /></template>
