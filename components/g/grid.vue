<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojuqj5b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojuqj5b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:grid" /></template>
