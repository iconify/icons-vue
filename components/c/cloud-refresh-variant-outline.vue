<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chz_ygbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chz_ygbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-refresh-variant-outline" /></template>
