<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmpyq4bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wmpyq4bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:crosshairs" /></template>
