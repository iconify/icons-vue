<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajxrk_byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ajxrk_byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:crown" /></template>
