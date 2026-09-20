<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn9rd4djt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn9rd4djt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:china-eastern-airlines" /></template>
