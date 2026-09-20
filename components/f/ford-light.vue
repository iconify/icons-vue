<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jye8v80ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jye8v80ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ford-light" /></template>
