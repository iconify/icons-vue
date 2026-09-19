<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed19s4bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ed19s4bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:glass-martini-alt" /></template>
