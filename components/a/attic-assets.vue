<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vju47qqkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vju47qqkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:attic-assets" /></template>
