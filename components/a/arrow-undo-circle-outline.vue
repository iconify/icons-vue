<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juv3elbto.css';
import '../../css/q/q-tflgzje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="juv3elbto"/><path class="q-tflgzje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-undo-circle-outline" /></template>
