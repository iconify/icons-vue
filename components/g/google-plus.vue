<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edo_wmwla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edo_wmwla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-plus" /></template>
