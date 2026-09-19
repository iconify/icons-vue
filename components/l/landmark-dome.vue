<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7fg6-4qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7fg6-4qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:landmark-dome" /></template>
