<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b51-lhp3z.css';
import '../../css/h/h1c-vo8ig.css';
import '../../css/g/gst7bffpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="b51-lhp3z"/><path class="h1c-vo8ig"/><path class="gst7bffpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:eight-key" /></template>
