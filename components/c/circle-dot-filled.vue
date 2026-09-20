<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdttf1bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fdttf1bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:circle-dot-filled" /></template>
