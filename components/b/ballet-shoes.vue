<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lked5vb0j.css';
import '../../css/q/qor4n6bhh.css';
import '../../css/q/q9olztvkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="lked5vb0j"/><path class="qor4n6bhh"/><path class="q9olztvkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:ballet-shoes" /></template>
