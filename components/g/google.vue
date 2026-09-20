<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu69v-s8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu69v-s8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:google" /></template>
