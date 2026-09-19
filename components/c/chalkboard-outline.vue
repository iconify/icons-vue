<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se8oa-w5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se8oa-w5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chalkboard-outline" /></template>
