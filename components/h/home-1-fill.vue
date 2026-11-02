<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcyxhlblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcyxhlblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:home-1-fill" /></template>
