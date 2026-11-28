<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-orlybmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-orlybmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:activity" /></template>
