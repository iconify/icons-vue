<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlo9x92kx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wlo9x92kx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:gamepad" /></template>
