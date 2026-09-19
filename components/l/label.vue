<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eek12hbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eek12hbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:label" /></template>
