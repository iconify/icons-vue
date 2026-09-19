<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le5ix3lon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="le5ix3lon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:cafe-sharp" /></template>
