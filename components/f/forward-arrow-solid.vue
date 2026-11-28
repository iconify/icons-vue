<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bffzsd8ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bffzsd8ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:forward-arrow-solid" /></template>
