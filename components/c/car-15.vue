<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqqep2yzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hqqep2yzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:car-15" /></template>
