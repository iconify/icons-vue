<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4_8vnbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l4_8vnbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:app-store" /></template>
