<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twkqxoofe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twkqxoofe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dashboard-square-add" /></template>
