<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee1hmhzww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee1hmhzww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:chevron-down-2" /></template>
