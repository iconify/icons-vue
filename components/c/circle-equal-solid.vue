<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj71y7bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj71y7bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-equal-solid" /></template>
