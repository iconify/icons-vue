<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flzd5qb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flzd5qb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:italic" /></template>
