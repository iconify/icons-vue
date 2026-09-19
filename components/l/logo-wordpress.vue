<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbyuj8lph.css';
import '../../css/e/eldvjb07a.css';
import '../../css/n/n-qmf6rfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rbyuj8lph"/><path class="eldvjb07a"/><path class="n-qmf6rfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-wordpress" /></template>
