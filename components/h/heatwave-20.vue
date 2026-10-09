<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6zve7bwi.css';
import '../../css/k/ku1wiibua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x6zve7bwi"/><path class="ku1wiibua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heatwave-20" /></template>
