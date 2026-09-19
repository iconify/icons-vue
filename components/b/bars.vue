<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcunykbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="rcunykbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bars" /></template>
