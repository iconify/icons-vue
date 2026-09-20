<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqc5__bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqc5__bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-settings" /></template>
