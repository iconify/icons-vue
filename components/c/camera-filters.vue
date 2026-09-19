<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lly1zw81b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lly1zw81b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:camera-filters" /></template>
