<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p50qzbcks.css';
import '../../css/w/w8f9-0zcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p50qzbcks"/><path class="w8f9-0zcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:copy" /></template>
