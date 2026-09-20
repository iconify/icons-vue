<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfzc1ffoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfzc1ffoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-eight-solid" /></template>
