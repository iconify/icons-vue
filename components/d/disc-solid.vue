<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp070hbdd.css';
import '../../css/k/kdxohkplo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dp070hbdd"/><path class="kdxohkplo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:disc-solid" /></template>
