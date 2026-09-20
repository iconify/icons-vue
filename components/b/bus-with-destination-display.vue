<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu8ksliog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tu8ksliog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bus-with-destination-display" /></template>
