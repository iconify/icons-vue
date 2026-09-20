<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehln14cwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehln14cwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-pickup" /></template>
