<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l82grjlfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l82grjlfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-bottom-down-outline" /></template>
