<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgsclgb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgsclgb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:authentik" /></template>
