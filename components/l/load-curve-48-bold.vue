<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8ue7ubrb.css';
import '../../css/o/o2ibymbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8ue7ubrb"/><path class="o2ibymbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-curve-48-bold" /></template>
