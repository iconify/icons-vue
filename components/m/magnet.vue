<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfrb4p-aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jfrb4p-aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:magnet" /></template>
