<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s42ri5_-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s42ri5_-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bus-stop" /></template>
