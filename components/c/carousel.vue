<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g957bft3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g957bft3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:carousel" /></template>
