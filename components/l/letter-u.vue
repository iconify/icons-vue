<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgff75bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgff75bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-u" /></template>
