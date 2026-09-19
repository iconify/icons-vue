<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjke9fltu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pjke9fltu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:import-all-mirrored" /></template>
