<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_8hp2bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_8hp2bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-text" /></template>
