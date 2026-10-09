<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyzs50b8b.css';
import '../../css/v/vceoc3bqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fyzs50b8b"/><path class="vceoc3bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leaf-20" /></template>
