<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n65kb88kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n65kb88kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:artcraft-dark" /></template>
