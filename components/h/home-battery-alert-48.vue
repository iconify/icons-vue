<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js4ro1b0l.css';
import '../../css/y/y-afnmd_s.css';
import '../../css/i/ikpbwe38b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="js4ro1b0l"/><path class="y-afnmd_s"/><path class="ikpbwe38b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-alert-48" /></template>
