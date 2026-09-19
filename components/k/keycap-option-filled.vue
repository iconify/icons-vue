<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9l8h93fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m9l8h93fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-option-filled" /></template>
