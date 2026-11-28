<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmdm1lbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmdm1lbdc primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:figma-duotone" /></template>
