<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoge7we4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoge7we4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:desktop" /></template>
