<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg_kyn8ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gg_kyn8ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flag" /></template>
