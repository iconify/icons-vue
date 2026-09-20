<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxlq8b69v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxlq8b69v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-twelve" /></template>
