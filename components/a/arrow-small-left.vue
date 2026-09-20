<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubn55kbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6,"height":16};
const content = `<path class="ubn55kbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-small-left" /></template>
