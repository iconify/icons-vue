<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz00iwbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":3200,"height":2048};
const content = `<path class="rz00iwbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:add-reaction" /></template>
