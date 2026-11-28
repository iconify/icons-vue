<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhrbp90le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhrbp90le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layers-merge-solid" /></template>
