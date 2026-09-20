<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr9hn0c9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr9hn0c9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-minus" /></template>
