<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm9ywsb4k.css';
import '../../css/f/ff6a3-ckh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lm9ywsb4k"/><path class="ff6a3-ckh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:clipboard-check" /></template>
