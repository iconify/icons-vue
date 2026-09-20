<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-og94iwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-og94iwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cookie-fill" /></template>
