<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nedfe4b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nedfe4b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:check-square" /></template>
