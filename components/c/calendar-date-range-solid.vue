<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuxx7n4ha.css';
import '../../css/x/xyaaz0bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuxx7n4ha"/><path clip-rule="evenodd" class="xyaaz0bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-date-range-solid" /></template>
