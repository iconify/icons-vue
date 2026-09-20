<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm55c-0qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nm55c-0qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:envelope" /></template>
