<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz_j2xb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz_j2xb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-line" /></template>
