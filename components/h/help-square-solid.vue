<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwu41bb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwu41bb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:help-square-solid" /></template>
