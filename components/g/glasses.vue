<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl5suacty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="xl5suacty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:glasses" /></template>
