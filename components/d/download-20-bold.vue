<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm6fofg8e.css';
import '../../css/j/j9dw79bzp.css';
import '../../css/o/oypn0j-vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hm6fofg8e"/><path class="j9dw79bzp"/><path class="oypn0j-vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:download-20-bold" /></template>
