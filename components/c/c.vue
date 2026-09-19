<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tk_jupb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="y9tk_jupb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:c" /></template>
