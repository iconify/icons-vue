<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u2398wb7u.css';
import '../../css/s/s76kbrb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":44,"height":44};
const content = `<g class="ft5dv1b6b"><rect class="u2398wb7u"/><path class="s76kbrb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ahooks" /></template>
