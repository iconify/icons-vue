<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_1dsscgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p_1dsscgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-up-from-water-pump" /></template>
