<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8ud6wbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8ud6wbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-wifi-bold" /></template>
