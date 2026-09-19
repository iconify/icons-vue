<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m03rwol8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m03rwol8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-g2-pro" /></template>
