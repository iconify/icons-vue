<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiqezpblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiqezpblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:car-fob" /></template>
