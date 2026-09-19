<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2-id4-1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2-id4-1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-2-thin" /></template>
