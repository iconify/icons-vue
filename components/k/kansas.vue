<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqrj_zbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qqrj_zbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kansas" /></template>
