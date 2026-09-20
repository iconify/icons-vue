<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqqs8_lie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqqs8_lie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:critical-light" /></template>
