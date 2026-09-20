<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hblpb_bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="hblpb_bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:dashboard" /></template>
