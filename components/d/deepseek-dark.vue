<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz5kt1b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yz5kt1b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deepseek-dark" /></template>
