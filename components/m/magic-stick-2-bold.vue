<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9e-2gbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9e-2gbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magic-stick-2-bold" /></template>
