<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1x2ejc7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r1x2ejc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bus-simple" /></template>
