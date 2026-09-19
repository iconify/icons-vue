<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or-3v0bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or-3v0bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bitcoin" /></template>
