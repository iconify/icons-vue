<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv4s0n6-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hv4s0n6-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:cloud-arrow-down" /></template>
