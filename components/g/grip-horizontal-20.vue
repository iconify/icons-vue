<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rinqamhsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rinqamhsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grip-horizontal-20" /></template>
