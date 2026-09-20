<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjtg53bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjtg53bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-down-thick" /></template>
