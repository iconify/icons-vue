<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhj13ubxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhj13ubxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bath" /></template>
