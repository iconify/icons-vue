<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ice-8pbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ice-8pbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dog-alt-filled" /></template>
