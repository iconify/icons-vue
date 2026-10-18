<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad97a97cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad97a97cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grip-vertical" /></template>
