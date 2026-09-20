<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh2xd8hhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh2xd8hhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:forward-email" /></template>
