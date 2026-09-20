<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmvvepbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vmvvepbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:borgmatic-light" /></template>
