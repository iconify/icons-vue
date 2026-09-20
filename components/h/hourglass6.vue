<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1x6-acbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="o1x6-acbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass6" /></template>
