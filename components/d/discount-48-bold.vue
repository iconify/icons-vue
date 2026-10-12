<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a88-_pnxg.css';
import '../../css/o/ocasejnlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a88-_pnxg"/><path class="ocasejnlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:discount-48-bold" /></template>
