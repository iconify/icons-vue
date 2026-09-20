<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ortm4mvgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":175.748,"height":105.761};
const content = `<path clip-rule="evenodd" class="ortm4mvgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:air-algerie" /></template>
