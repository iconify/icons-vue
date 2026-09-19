<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4ur-e1rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4ur-e1rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:hornbill" /></template>
