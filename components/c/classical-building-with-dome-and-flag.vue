<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwyxdm3le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hwyxdm3le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:classical-building-with-dome-and-flag" /></template>
