<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4mabsbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4mabsbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:corner-top-right" /></template>
