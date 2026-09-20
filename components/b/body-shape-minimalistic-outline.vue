<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2s8njbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2s8njbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-minimalistic-outline" /></template>
