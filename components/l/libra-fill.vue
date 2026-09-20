<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve6zp4c2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6zp4c2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:libra-fill" /></template>
