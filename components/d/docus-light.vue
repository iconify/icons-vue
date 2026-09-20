<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvcslwbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":32};
const content = `<path clip-rule="evenodd" class="kvcslwbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:docus-light" /></template>
