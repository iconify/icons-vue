<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_4v9bbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_4v9bbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-manual-input-solid" /></template>
