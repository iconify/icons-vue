<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6w625b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u6w625b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:distribute-vertical-20" /></template>
