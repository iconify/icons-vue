<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkzkov_zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mkzkov_zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:life-jacket" /></template>
