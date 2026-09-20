<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3368wbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r3368wbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:frowning-face-with-head-bandage-in-circle" /></template>
