<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h72dw-q8s.css';
import '../../css/a/az0wvsxpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h72dw-q8s"/><path class="az0wvsxpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kick-scooter-48-bold" /></template>
