<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hicpc4xzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hicpc4xzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-octagon-solid" /></template>
