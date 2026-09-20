<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1z1hbc7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n1z1hbc7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:accordion" /></template>
