<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4elc1-ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n4elc1-ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-lightning-rain-fill" /></template>
