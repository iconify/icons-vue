<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o053b3bvz.css';
import '../../css/u/u2os-ab_w.css';
import '../../css/n/n6lpwabqu.css';
import '../../css/n/n-dzcccws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o053b3bvz"/><path class="u2os-ab_w"/><path class="n6lpwabqu"/><path class="n-dzcccws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:calendar-user" /></template>
