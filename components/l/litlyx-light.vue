<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4se6pb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e4se6pb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:litlyx-light" /></template>
