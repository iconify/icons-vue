<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf283dbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf283dbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:beaker" /></template>
