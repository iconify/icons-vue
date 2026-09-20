<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmdhz5s5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmdhz5s5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-multiple" /></template>
