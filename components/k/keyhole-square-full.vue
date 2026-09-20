<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exdxmabyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exdxmabyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:keyhole-square-full" /></template>
