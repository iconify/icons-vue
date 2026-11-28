<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vep_7fb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vep_7fb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-right-circle-solid" /></template>
