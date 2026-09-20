<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm4ixobxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sm4ixobxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:cannon" /></template>
