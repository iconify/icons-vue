<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhrh62b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhrh62b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-waves" /></template>
