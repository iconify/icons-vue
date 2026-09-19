<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz92fdcew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz92fdcew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-game" /></template>
