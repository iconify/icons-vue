<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axful0b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="axful0b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-shape-turn-up-right" /></template>
