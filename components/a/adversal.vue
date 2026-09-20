<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cevas8bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cevas8bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:adversal" /></template>
