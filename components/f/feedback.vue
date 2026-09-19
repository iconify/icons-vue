<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4_i2lb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="v4_i2lb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:feedback" /></template>
