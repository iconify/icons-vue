<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af2lrjbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af2lrjbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-plus" /></template>
