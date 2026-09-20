<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgy5qiwxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vgy5qiwxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:deer-head-with-antlers" /></template>
