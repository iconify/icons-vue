<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpp1pked.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbpp1pked"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:euro" /></template>
