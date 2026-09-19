<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-9l5vbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-9l5vbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-split" /></template>
