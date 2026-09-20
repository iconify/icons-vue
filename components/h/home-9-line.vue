<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg94i5mch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg94i5mch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-9-line" /></template>
