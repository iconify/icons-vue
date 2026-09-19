<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5pd5bcbi.css';
import '../../css/q/q33pllwot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5pd5bcbi"/><path class="q33pllwot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-outer-filled" /></template>
