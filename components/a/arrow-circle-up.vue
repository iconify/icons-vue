<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yurwaccmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yurwaccmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:arrow-circle-up" /></template>
