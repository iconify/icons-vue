<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w71383bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w71383bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keyhelp-dark" /></template>
