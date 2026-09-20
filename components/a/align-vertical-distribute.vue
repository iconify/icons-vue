<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfc18wb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pfc18wb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:align-vertical-distribute" /></template>
