<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2n0ibczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2n0ibczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chevron-expand-y" /></template>
