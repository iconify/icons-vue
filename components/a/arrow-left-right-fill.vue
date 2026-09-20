<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io6equpbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io6equpbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-right-fill" /></template>
