<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9d6xob5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m9d6xob5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:key" /></template>
