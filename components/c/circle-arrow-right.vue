<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lznsx1kgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lznsx1kgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-right" /></template>
