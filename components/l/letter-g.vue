<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwwgftb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwwgftb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-g" /></template>
