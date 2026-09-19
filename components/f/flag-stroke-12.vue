<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzknwlbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vzknwlbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flag-stroke-12" /></template>
