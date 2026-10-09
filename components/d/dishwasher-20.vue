<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1middb0q.css';
import '../../css/o/o42c9jpgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1middb0q"/><path class="o42c9jpgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dishwasher-20" /></template>
