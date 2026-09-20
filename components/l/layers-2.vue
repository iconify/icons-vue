<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlam41bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlam41bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:layers-2" /></template>
