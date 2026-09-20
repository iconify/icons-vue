<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rar_2_a4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rar_2_a4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:acorn" /></template>
