<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enmz8v5ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="enmz8v5ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cargobike-and-rupee" /></template>
