<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3kuv-btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g3kuv-btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:appveyor" /></template>
