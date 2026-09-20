<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7w8d9joa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i7w8d9joa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bookstack-dark" /></template>
