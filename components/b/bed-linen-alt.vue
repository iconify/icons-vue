<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm8myvyyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm8myvyyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bed-linen-alt" /></template>
