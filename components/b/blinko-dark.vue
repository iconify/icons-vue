<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-qh99buv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-qh99buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:blinko-dark" /></template>
