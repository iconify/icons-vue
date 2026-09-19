<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g169grb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g169grb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-flushed" /></template>
