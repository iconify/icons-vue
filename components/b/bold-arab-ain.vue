<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4e5dcc-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o4e5dcc-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-arab-ain" /></template>
