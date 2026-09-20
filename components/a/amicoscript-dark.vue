<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1rk6ccif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n1rk6ccif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amicoscript-dark" /></template>
