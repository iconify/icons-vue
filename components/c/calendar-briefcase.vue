<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o053b3bvz.css';
import '../../css/b/bps76ebgq.css';
import '../../css/f/fw1xawbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o053b3bvz"/><path class="bps76ebgq"/><path class="fw1xawbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:calendar-briefcase" /></template>
