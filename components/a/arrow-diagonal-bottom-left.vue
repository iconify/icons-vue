<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae7x5gbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ae7x5gbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-diagonal-bottom-left" /></template>
