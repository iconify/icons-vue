<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eni9_nbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eni9_nbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-right-bold-outline" /></template>
