<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyezpzb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyezpzb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-right-solid" /></template>
