<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ychnccbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="ychnccbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:arrow-both-direction-horizontal-1" /></template>
