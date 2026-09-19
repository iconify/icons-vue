<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usz0agbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usz0agbob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flag-sharp" /></template>
