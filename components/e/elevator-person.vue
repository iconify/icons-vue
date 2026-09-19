<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-vfrub4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-vfrub4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:elevator-person" /></template>
