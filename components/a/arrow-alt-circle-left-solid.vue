<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foz3lr1_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="foz3lr1_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:arrow-alt-circle-left-solid" /></template>
