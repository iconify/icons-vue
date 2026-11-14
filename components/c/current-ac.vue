<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzz5bnbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzz5bnbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:current-ac" /></template>
