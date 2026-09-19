<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-xm_j6rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="q-xm_j6rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-lizard-o" /></template>
