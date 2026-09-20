<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w99nqwb2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w99nqwb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:focus-points-remix" /></template>
