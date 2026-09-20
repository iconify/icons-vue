<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzoxkcclh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzoxkcclh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-edit" /></template>
