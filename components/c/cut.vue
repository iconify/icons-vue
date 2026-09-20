<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n25yeq5ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n25yeq5ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:cut" /></template>
