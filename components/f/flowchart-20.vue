<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlfukpbru.css';
import '../../css/s/sgrfz4b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jlfukpbru"/><path class="sgrfz4b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flowchart-20" /></template>
