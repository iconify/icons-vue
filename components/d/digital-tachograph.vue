<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srfwtrbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="srfwtrbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:digital-tachograph" /></template>
