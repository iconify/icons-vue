<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr2xlsbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hr2xlsbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:columns" /></template>
