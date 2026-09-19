<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7ns8abmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="o7ns8abmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fire" /></template>
