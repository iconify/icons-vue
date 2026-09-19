<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxkaktb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oxkaktb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:code-compare" /></template>
