<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nirzt8hqp.css';
import '../../css/k/kite7abkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nirzt8hqp"/><path class="kite7abkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-sparkle-20-bold" /></template>
