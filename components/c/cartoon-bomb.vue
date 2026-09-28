<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osl37rbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="osl37rbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cartoon-bomb" /></template>
