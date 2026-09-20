<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r095fdb0a.css';
import '../../css/s/sgkeqm1ah.css';
import '../../css/r/ruj0ehbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r095fdb0a"/><path class="sgkeqm1ah"/><path class="ruj0ehbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:copy" /></template>
