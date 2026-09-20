<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4yb8v8ih.css';
import '../../css/u/u-uywrbac.css';
import '../../css/g/gzifgrbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4yb8v8ih"/><path class="u-uywrbac"/><path class="gzifgrbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:exit-o" /></template>
