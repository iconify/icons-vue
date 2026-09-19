<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx1dvp6hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx1dvp6hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:compass-filled" /></template>
