<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4aub3bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4aub3bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-outline" /></template>
