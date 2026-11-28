<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peuvlzbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="peuvlzbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-solid" /></template>
