<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh23dybnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh23dybnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:figure-fill" /></template>
