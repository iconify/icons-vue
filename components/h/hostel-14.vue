<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1lp2mbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w1lp2mbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:hostel-14" /></template>
