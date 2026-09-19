<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m360l3zaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m360l3zaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-tab" /></template>
