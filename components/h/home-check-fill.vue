<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw8shqb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw8shqb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-check-fill" /></template>
