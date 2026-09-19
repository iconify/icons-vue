<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0jwkhb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0jwkhb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:functions" /></template>
