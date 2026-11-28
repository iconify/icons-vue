<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq15dbigt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq15dbigt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:candy" /></template>
