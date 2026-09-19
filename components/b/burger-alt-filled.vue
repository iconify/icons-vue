<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvcz6hbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvcz6hbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:burger-alt-filled" /></template>
