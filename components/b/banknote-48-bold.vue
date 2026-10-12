<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ejkab4k.css';
import '../../css/l/l54utlx8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r9ejkab4k"/><path class="l54utlx8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:banknote-48-bold" /></template>
