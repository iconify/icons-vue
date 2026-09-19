<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3ljxyeyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="j3ljxyeyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:delete" /></template>
