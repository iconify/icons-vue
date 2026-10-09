<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtljkfb6y.css';
import '../../css/t/tkx4pub6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jtljkfb6y"/><path class="tkx4pub6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-charging-20-bold" /></template>
