<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb_59depv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_59depv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:arcade" /></template>
