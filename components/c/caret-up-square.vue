<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb-ee9b3j.css';
import '../../css/i/ijg5zh-jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb-ee9b3j"/><path class="ijg5zh-jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-up-square" /></template>
