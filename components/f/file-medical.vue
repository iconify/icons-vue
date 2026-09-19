<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm6nu5b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qm6nu5b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-medical" /></template>
