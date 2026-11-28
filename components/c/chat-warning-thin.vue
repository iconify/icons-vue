<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0_igibyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g0_igibyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chat-warning-thin" /></template>
