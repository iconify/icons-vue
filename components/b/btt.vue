<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j29s27bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j29s27bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btt" /></template>
