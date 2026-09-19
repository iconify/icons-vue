<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3f1dnbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n3f1dnbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:lifesaver" /></template>
