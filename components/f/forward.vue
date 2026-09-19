<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj6e5wb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aj6e5wb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:forward" /></template>
