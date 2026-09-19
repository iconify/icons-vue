<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb2ln4bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb2ln4bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-virus" /></template>
