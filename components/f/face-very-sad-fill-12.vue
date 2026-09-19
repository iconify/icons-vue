<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l39qosc6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="l39qosc6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-sad-fill-12" /></template>
