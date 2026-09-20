<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz0b9lmct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz0b9lmct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:line-out" /></template>
