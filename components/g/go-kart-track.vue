<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz-bawb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz-bawb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:go-kart-track" /></template>
