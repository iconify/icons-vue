<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypr4kwbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypr4kwbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:like" /></template>
