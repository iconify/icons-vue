<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj2cj9b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="jj2cj9b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grip-lines-vertical" /></template>
