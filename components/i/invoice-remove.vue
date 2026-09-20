<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbnmj0bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbnmj0bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-remove" /></template>
