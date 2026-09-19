<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1hcdyb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1hcdyb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:columns" /></template>
