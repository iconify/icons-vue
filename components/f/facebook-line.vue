<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmc74g-ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmc74g-ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:facebook-line" /></template>
