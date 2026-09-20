<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq8b29b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq8b29b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:following" /></template>
