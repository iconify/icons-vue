<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbaxuqr4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbaxuqr4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:line-line" /></template>
