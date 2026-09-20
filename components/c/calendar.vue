<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omt14xb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="omt14xb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:calendar" /></template>
