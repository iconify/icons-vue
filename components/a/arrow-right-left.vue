<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxucp5bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxucp5bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-right-left" /></template>
