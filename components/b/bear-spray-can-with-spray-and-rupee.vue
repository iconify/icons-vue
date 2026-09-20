<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqh2ic0-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yqh2ic0-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-rupee" /></template>
