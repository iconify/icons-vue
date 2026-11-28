<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngo_hc0bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngo_hc0bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:duck-solid" /></template>
