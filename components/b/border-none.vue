<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd8h75b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dd8h75b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:border-none" /></template>
