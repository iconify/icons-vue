<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqe3_vbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqe3_vbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:command-solid" /></template>
