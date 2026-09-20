<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0itzf1zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0itzf1zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cypht-light" /></template>
