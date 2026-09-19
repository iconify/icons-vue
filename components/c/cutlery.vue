<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znwf89bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1792};
const content = `<path class="znwf89bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:cutlery" /></template>
