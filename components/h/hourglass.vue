<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaadjjbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1472};
const content = `<path class="eaadjjbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:hourglass" /></template>
