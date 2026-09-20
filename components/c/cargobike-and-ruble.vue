<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czomedcym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="czomedcym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-and-ruble" /></template>
