<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de9w25bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de9w25bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrange-square2-filled" /></template>
