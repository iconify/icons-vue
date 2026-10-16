<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxzebdb5x.css';
import '../../css/r/ro3ticcmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxzebdb5x"/><path class="ro3ticcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folders-48-bold" /></template>
