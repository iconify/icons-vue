<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0lclmplr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r0lclmplr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:compact-box-truck-with-heavy-six-point-asterisk" /></template>
