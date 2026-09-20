<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7jaokete.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n7jaokete"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:car-shower-head" /></template>
