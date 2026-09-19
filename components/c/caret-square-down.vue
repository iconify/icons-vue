<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4p_33ayd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="a4p_33ayd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:caret-square-down" /></template>
