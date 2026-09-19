<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j25ju4bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="j25ju4bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bong" /></template>
