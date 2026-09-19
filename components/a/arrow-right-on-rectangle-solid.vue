<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inbfl_ipd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inbfl_ipd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-right-on-rectangle-solid" /></template>
