<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvq0_nb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="yvq0_nb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:equalizer" /></template>
