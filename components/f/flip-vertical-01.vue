<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-l02b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da-l02b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flip-vertical-01" /></template>
