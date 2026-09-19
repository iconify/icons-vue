<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c83t9k23a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c83t9k23a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-left-arrow-circle" /></template>
