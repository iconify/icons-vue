<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9yvzfgbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="r9yvzfgbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hospital-11" /></template>
