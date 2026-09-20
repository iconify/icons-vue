<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adyc_d18v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adyc_d18v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gate-not" /></template>
