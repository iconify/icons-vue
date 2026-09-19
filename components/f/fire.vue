<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej-tn9ioj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ej-tn9ioj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:fire" /></template>
