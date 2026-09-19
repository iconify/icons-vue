<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmzo3dvgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rmzo3dvgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bow" /></template>
