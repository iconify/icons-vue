<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihmh29bqx.css';
import '../../css/l/lhghp8bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ihmh29bqx"/><path clip-rule="evenodd" class="lhghp8bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-date-range-16-solid" /></template>
