<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to33eh6vt.css';
import '../../css/t/t6ndzsb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="to33eh6vt"/><path class="t6ndzsb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:envelopes" /></template>
