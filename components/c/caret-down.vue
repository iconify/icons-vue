<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc5ow5b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":384};
const content = `<path class="xc5ow5b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:caret-down" /></template>
