<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc3j3dfwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc3j3dfwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:book-check" /></template>
