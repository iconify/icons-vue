<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_b9ccaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="rp_b9ccaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-pointer" /></template>
