<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf2w5qbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf2w5qbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-info" /></template>
