<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqd7lbb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vqd7lbb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-rain-48-bold" /></template>
