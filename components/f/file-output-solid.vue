<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc7023fup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc7023fup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-output-solid" /></template>
