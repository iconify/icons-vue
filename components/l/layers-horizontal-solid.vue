<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-jeeboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-jeeboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-horizontal-solid" /></template>
