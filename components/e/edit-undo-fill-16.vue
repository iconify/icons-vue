<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysl5nf33v.css';
import '../../css/v/vjs9accli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ysl5nf33v"/><path class="vjs9accli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:edit-undo-fill-16" /></template>
