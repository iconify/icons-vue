<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdfw7y4er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vdfw7y4er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:line-dashed-duotone" /></template>
