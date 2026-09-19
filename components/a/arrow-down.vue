<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjb-r5bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="pjb-r5bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:arrow-down" /></template>
