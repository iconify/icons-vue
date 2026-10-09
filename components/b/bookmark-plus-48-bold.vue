<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7ue9wb8n.css';
import '../../css/r/re6y0hbtf.css';
import '../../css/j/jfdfjcbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b7ue9wb8n"/><path class="re6y0hbtf"/><path class="jfdfjcbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-plus-48-bold" /></template>
