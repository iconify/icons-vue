<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y88wtbtkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y88wtbtkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ankh-on-square" /></template>
