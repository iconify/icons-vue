<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzdnmsb-q.css';
import '../../css/t/ty_2is9tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dzdnmsb-q"/><circle class="ty_2is9tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-arab-dad" /></template>
