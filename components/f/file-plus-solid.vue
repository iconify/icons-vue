<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6h1arbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t6h1arbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-plus-solid" /></template>
