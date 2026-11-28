<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms01scbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms01scbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-brain-solid" /></template>
