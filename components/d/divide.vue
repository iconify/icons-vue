<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3saow1yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3saow1yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:divide" /></template>
