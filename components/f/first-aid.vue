<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okyebdcgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okyebdcgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:first-aid" /></template>
