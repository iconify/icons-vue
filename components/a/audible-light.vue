<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnwj53bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnwj53bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:audible-light" /></template>
