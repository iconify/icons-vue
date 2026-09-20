<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2sf82c6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2sf82c6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-variant-alert" /></template>
