<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdf4gyzkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bdf4gyzkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:fire" /></template>
