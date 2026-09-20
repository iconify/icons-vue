<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm5iofbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hm5iofbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-horizontal-up-stipple" /></template>
