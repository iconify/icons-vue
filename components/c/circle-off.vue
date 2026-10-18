<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-vkd2r7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-vkd2r7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-off" /></template>
