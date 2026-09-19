<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgqucl06k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jgqucl06k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:folder-plus" /></template>
