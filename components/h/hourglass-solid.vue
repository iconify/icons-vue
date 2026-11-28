<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqq99_76y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqq99_76y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hourglass-solid" /></template>
