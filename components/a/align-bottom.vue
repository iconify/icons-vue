<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jddyy98pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jddyy98pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-bottom" /></template>
