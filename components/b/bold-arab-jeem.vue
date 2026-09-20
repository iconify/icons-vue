<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u21y36n3m.css';
import '../../css/q/qtj8v8b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u21y36n3m"/><circle class="qtj8v8b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-arab-jeem" /></template>
