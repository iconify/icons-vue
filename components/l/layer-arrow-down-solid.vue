<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqgaffhxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqgaffhxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layer-arrow-down-solid" /></template>
