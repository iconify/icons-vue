<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d879w_odg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d879w_odg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-round" /></template>
