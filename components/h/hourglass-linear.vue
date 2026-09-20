<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z52bhccup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z52bhccup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hourglass-linear" /></template>
