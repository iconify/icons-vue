<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuu_75j-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuu_75j-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-x-solid" /></template>
