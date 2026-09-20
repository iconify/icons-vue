<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaycst59r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaycst59r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-projectile" /></template>
