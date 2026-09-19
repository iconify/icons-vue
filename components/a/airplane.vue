<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpyssxbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jpyssxbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:airplane" /></template>
