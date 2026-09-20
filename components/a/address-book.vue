<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0ttoybfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t0ttoybfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:address-book" /></template>
