<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y002-9bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y002-9bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-long-line" /></template>
