<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhtqtnb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mhtqtnb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:circle-filled-32" /></template>
