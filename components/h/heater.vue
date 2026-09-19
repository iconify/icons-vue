<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap8ol18hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap8ol18hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:heater" /></template>
