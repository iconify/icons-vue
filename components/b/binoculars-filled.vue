<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsin-x7co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zsin-x7co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:binoculars-filled" /></template>
