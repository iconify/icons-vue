<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qet9msrbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qet9msrbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-meteor" /></template>
