<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl113ubjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wl113ubjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:doi-square" /></template>
