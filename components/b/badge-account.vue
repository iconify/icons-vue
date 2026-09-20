<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1fub-b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1fub-b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:badge-account" /></template>
