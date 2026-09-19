<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7foklbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7foklbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dashboard" /></template>
