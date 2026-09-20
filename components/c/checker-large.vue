<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2z2u4mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="xi2z2u4mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:checker-large" /></template>
