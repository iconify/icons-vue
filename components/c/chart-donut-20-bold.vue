<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6-c2yag.css';
import '../../css/i/ihj-8acvw.css';
import '../../css/b/bdln6g71h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aa6-c2yag"/><path class="ihj-8acvw"/><path class="bdln6g71h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-donut-20-bold" /></template>
