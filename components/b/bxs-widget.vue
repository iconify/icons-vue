<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_nr1-bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_nr1-bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-widget" /></template>
