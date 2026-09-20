<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9ujhk2vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q9ujhk2vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:fill-16" /></template>
