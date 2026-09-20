<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0u9rabbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="n0u9rabbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:global-plant" /></template>
