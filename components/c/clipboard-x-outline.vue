<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4s7ye-xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h4s7ye-xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-x-outline" /></template>
