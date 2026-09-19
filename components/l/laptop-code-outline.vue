<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucm_evpsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucm_evpsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:laptop-code-outline" /></template>
