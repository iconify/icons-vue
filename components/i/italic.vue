<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4m3oxble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n4m3oxble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:italic" /></template>
