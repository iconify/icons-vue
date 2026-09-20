<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5g4w9b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5g4w9b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-off-outline" /></template>
