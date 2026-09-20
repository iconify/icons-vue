<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znih9hbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znih9hbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gradient-horizontal" /></template>
