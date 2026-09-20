<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhnso0b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhnso0b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:align-left" /></template>
