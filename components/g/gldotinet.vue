<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aoc9a1biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoc9a1biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gldotinet" /></template>
