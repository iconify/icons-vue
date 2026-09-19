<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpsrhxbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jpsrhxbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flash-off-filled" /></template>
