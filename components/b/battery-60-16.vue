<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6c2rnb4s.css';
import '../../css/f/ffaginb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6c2rnb4s"/><path clip-rule="evenodd" class="ffaginb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:battery-60-16" /></template>
