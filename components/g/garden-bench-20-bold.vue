<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcgtjcb0f.css';
import '../../css/f/fmoi5vldd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kcgtjcb0f"/><path class="fmoi5vldd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:garden-bench-20-bold" /></template>
