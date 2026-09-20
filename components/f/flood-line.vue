<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew9lb30nf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew9lb30nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flood-line" /></template>
