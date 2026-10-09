<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyrpv8pvm.css';
import '../../css/o/o8g693dbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zyrpv8pvm"/><path class="o8g693dbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dashboard-20" /></template>
