<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n42446fje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n42446fje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-plus" /></template>
