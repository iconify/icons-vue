<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syffbkb-v.css';
import '../../css/j/j04q1cb1h.css';
import '../../css/z/zkta6vbnt.css';
import '../../css/p/p4fg2sbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="syffbkb-v"/><path class="j04q1cb1h"/><path class="zkta6vbnt"/><path class="p4fg2sbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geiger-counter-48" /></template>
