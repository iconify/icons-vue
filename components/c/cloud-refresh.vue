<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq2fpc9nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq2fpc9nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-refresh" /></template>
