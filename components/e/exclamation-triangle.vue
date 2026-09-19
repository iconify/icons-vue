<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox2dgjb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ox2dgjb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:exclamation-triangle" /></template>
