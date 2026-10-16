<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6or-r9if.css';
import '../../css/g/ggfao8bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p6or-r9if"/><path class="ggfao8bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dew-20-bold" /></template>
