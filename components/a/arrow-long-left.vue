<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x467bpb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x467bpb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-long-left" /></template>
