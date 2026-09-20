<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4d_1lavu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4d_1lavu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:login" /></template>
