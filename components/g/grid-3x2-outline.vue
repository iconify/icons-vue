<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj6svecim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vj6svecim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x2-outline" /></template>
