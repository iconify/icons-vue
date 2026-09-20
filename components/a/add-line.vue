<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnkxhsbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnkxhsbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-line" /></template>
