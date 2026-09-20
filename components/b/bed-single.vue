<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjbnhbcyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjbnhbcyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bed-single" /></template>
