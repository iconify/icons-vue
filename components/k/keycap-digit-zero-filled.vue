<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dim6cfwha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dim6cfwha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-zero-filled" /></template>
