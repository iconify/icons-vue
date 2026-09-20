<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvgij0b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xvgij0b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:circle-16" /></template>
