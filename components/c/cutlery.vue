<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg7zkcbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg7zkcbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:cutlery" /></template>
