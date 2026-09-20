<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3-u2ubdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f3-u2ubdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bench-with-backrest-in-rectangular-shelter" /></template>
