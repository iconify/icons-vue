<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkoka4bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkoka4bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-single-clockwise" /></template>
