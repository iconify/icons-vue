<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1lj5vbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a1lj5vbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grimace" /></template>
