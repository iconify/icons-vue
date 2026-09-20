<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds95o_99b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds95o_99b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jdoodle" /></template>
