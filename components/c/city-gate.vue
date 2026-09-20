<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl32-54lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xl32-54lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:city-gate" /></template>
