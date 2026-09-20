<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1nhcybrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1nhcybrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:contact-mail-outline" /></template>
