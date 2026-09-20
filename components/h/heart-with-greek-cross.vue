<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k685z7nro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k685z7nro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-with-greek-cross" /></template>
