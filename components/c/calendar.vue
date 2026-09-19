<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9nbzj2qc.css';
import '../../css/n/nzs58m68f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="j9nbzj2qc"/><path class="nzs58m68f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:calendar" /></template>
