<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufpp1mb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufpp1mb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:key-line" /></template>
