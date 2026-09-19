<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz3hddb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pz3hddb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:baseball" /></template>
