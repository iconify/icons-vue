<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yox9j2bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="yox9j2bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:entrance-alt1-11" /></template>
