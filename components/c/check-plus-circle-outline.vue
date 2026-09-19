<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxai6ezyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxai6ezyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:check-plus-circle-outline" /></template>
