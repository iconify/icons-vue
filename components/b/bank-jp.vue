<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_0ffkbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o_0ffkbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bank-jp" /></template>
