<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjmw7zpnx.css';
import '../../css/o/oz3hiebwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rjmw7zpnx"/><path class="oz3hiebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:copilot-16" /></template>
