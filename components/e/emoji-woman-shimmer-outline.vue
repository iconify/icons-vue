<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krpq4dddo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krpq4dddo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-woman-shimmer-outline" /></template>
