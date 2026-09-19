<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5zi9c24n.css';
import '../../css/j/ji_uifbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5zi9c24n"/><path class="ji_uifbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:location-on" /></template>
