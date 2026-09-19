<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-tflgzje.css';
import '../../css/p/png1nf7mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-tflgzje"/><path class="png1nf7mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-down-circle-outline" /></template>
