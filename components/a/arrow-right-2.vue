<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am2uaik4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am2uaik4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-2" /></template>
