<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg96uj61p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg96uj61p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-1-solid" /></template>
