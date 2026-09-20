<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxqaj3bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxqaj3bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:aioz" /></template>
