<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbjn0qbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbjn0qbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-reply" /></template>
