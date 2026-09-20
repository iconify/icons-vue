<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxsm46bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxsm46bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:angle-up" /></template>
