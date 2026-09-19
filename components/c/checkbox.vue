<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f324_hb1n.css';
import '../../css/e/edm1wthdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":44,"height":44};
const content = `<rect class="f324_hb1n"/><path class="edm1wthdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:checkbox" /></template>
