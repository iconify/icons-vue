<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4jd6hbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i4jd6hbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inductor-48-bold" /></template>
