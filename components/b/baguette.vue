<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1z1z7oaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i1z1z7oaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:baguette" /></template>
