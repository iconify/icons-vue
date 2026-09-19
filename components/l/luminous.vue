<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1s60ybug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1s60ybug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:luminous" /></template>
