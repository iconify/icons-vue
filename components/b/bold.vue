<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu_4dpbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gu_4dpbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:bold" /></template>
