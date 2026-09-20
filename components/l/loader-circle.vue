<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhr2xybsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zhr2xybsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:loader-circle" /></template>
