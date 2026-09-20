<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imjigbc6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imjigbc6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:building" /></template>
