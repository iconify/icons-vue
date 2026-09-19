<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc86c7rgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="tc86c7rgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:connection" /></template>
