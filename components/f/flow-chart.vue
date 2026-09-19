<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkhi9lbht.css';
import '../../css/q/qvchyyb3r.css';
import '../../css/s/svglptr5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tkhi9lbht"/><path class="qvchyyb3r"/><path class="svglptr5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:flow-chart" /></template>
