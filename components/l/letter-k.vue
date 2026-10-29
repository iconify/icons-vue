<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozz1ixbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozz1ixbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-k" /></template>
