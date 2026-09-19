<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l17hfdciu.css';
import '../../css/d/dtwl1wjmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l17hfdciu"/><path class="dtwl1wjmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-x-filled" /></template>
