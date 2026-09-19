<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs0839n8x.css';
import '../../css/t/ta7x8sbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cs0839n8x"/><path class="ta7x8sbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:catalog-publish" /></template>
