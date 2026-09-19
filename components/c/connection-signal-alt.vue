<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd5t47bei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bd5t47bei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection-signal-alt" /></template>
