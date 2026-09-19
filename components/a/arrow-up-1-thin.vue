<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7kyt3olr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7kyt3olr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-1-thin" /></template>
