<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgsw6jy6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgsw6jy6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-spin" /></template>
