<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxmh49ktf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sxmh49ktf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:icicles" /></template>
