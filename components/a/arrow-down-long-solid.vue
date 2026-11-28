<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxn1b1byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxn1b1byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-long-solid" /></template>
