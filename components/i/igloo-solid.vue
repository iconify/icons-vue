<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylnwac1ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylnwac1ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:igloo-solid" /></template>
