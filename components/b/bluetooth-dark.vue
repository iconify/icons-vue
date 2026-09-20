<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzbpc3vpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzbpc3vpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bluetooth-dark" /></template>
