<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgu2i2bgi.css';
import '../../css/g/gyh2arbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mgu2i2bgi"/><path clip-rule="evenodd" class="gyh2arbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:fullscreen-16" /></template>
