<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxe094bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxe094bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:abb-radio" /></template>
