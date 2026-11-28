<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1lkf0bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1lkf0bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:circle-0" /></template>
