<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj4uatshi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj4uatshi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calculator" /></template>
