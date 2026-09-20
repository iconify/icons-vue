<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4p_t1bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i4p_t1bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coughing-face-in-circle" /></template>
