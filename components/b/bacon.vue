<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvsi6gbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvsi6gbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bacon" /></template>
