<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfrr6dbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfrr6dbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:heading-level-5" /></template>
