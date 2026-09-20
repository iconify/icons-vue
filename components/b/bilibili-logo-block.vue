<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca8yc2baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca8yc2baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bilibili-logo-block" /></template>
