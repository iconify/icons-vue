<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb4ig9byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yb4ig9byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-molar-tooth" /></template>
