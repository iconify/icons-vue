<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0jr5uboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l0jr5uboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-open-gabled-building-with-chimney" /></template>
