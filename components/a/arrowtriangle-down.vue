<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfy11pvfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gfy11pvfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowtriangle-down" /></template>
