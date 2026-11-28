<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wung1w3oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wung1w3oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-check" /></template>
