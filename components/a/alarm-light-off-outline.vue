<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zefx5bxey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zefx5bxey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-light-off-outline" /></template>
