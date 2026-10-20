<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5v9g9qtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5v9g9qtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caps-lock-48-bold" /></template>
