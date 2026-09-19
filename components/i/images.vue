<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utpg_nbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="utpg_nbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:images" /></template>
