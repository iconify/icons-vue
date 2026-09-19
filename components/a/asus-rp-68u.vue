<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtvz4qqfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtvz4qqfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:asus-rp-68u" /></template>
