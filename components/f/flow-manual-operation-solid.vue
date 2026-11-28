<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo37sdstw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo37sdstw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-manual-operation-solid" /></template>
