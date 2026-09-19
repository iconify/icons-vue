<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqcm5iqdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cqcm5iqdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:clone" /></template>
