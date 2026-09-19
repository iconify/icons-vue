<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyl68vb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="dyl68vb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:align-right" /></template>
