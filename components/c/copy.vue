<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smegf5bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="smegf5bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:copy" /></template>
