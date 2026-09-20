<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzu4lnr2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qzu4lnr2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:corner-top-right" /></template>
