<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/empx9xa-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="empx9xa-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:add-filled" /></template>
