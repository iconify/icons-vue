<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbqt5xw6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mbqt5xw6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hawaii" /></template>
