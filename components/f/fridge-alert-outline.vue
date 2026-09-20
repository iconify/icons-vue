<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjx9z_bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjx9z_bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-alert-outline" /></template>
