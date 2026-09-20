<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6hitmb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6hitmb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-auto-outline" /></template>
