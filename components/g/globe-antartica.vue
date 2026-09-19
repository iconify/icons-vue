<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yev1t9yns.css';
import '../../css/z/zv4wep4nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yev1t9yns"/><path class="zv4wep4nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-antartica" /></template>
