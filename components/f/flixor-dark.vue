<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udeylcb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udeylcb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flixor-dark" /></template>
