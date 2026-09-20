<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-f0xhbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-f0xhbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:align-left" /></template>
