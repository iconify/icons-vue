<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4n0e7nyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4n0e7nyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-compare" /></template>
