<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db4q_oyyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="db4q_oyyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:cpu" /></template>
